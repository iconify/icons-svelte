<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg964tbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg964tbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-gear" {...props}></Icon>
