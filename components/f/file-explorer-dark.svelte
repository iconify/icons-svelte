<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4v7vnbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4v7vnbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-explorer-dark" {...props}></Icon>
