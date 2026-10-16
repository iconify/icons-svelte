<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8phqb4wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f8phqb4wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cavity-wall-20-bold" {...props}></Icon>
