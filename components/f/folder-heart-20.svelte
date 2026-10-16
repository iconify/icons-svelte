<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3me-4caq.css';
import '../../css/o/oixzy0brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="oixzy0brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-heart-20" {...props}></Icon>
