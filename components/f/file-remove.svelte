<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_0e_e0e.css';
import '../../css/y/yf1-nhwqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-_0e_e0e"/><path class="yf1-nhwqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-remove" {...props}></Icon>
