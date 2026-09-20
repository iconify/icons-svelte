<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx9qcfbri.css';
import '../../css/e/ewlo7db9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hx9qcfbri"/><path class="ewlo7db9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-pdm" {...props}></Icon>
