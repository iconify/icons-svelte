<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcis7r43e.css';
import '../../css/r/rgfwyacmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xcis7r43e"/><path class="rgfwyacmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-charging" {...props}></Icon>
