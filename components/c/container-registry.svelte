<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzesfbb8z.css';
import '../../css/q/qccj0vbum.css';
import '../../css/d/dlp7nstpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzesfbb8z"/><path class="qccj0vbum"/><circle class="dlp7nstpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:container-registry" {...props}></Icon>
