<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grp69rnla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grp69rnla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:exchange-01" {...props}></Icon>
