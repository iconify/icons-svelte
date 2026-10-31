<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzs66bwwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzs66bwwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:headset-gloss" {...props}></Icon>
