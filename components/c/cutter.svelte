<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up5bodb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="up5bodb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:cutter" {...props}></Icon>
