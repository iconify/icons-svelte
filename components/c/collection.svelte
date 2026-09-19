<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_69iu2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl_69iu2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:collection" {...props}></Icon>
