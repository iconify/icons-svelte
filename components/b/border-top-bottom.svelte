<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh7hngbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="rh7hngbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top-bottom" {...props}></Icon>
