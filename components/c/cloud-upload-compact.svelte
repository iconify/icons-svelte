<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd0mwet8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sd0mwet8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:cloud-upload-compact" {...props}></Icon>
