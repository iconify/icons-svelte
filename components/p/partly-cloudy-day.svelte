<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1pqvb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jv1pqvb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:partly-cloudy-day" {...props}></Icon>
