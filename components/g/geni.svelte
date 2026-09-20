<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4n5wplky.css';
import '../../css/o/ow091_bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4n5wplky"/><path class="ow091_bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:geni" {...props}></Icon>
