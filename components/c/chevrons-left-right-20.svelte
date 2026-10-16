<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi7ji7b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wi7ji7b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-right-20" {...props}></Icon>
