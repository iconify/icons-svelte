<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt8b9db9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vt8b9db9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:move-alt" {...props}></Icon>
