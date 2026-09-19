<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6_s7g3ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q6_s7g3ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:align-full-width" {...props}></Icon>
