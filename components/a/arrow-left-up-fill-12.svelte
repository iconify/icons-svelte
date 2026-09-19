<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy6uo1b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yy6uo1b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-up-fill-12" {...props}></Icon>
