<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvoikgb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dvoikgb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:baby" {...props}></Icon>
