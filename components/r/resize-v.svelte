<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyn5uqikh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tyn5uqikh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:resize-v" {...props}></Icon>
