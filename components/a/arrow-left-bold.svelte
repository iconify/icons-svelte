<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5t3am54q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h5t3am54q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-left-bold" {...props}></Icon>
