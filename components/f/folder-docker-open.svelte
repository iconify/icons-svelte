<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwia98bio.css';
import '../../css/y/yd8vu0b0e.css';
import '../../css/s/sd838mbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pwia98bio"/><path class="yd8vu0b0e"/><path class="sd838mbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-docker-open" {...props}></Icon>
