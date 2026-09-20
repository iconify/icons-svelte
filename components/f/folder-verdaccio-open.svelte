<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urkx-c35c.css';
import '../../css/g/gjo-eg8gx.css';
import '../../css/r/rqz-hwa9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="urkx-c35c"/><path class="gjo-eg8gx"/><path class="rqz-hwa9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-verdaccio-open" {...props}></Icon>
