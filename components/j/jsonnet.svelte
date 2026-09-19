<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx4_asb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rx4_asb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jsonnet" {...props}></Icon>
