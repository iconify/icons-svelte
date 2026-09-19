<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yogscsb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yogscsb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:minus" {...props}></Icon>
