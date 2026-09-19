<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jteibjb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jteibjb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:nav-2-d-map-view" {...props}></Icon>
