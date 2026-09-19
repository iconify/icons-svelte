<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcez0mbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":384};
const content = `<path class="xcez0mbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:code-setting" {...props}></Icon>
