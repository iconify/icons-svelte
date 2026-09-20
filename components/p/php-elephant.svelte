<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1hlh30_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j1hlh30_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:php-elephant" {...props}></Icon>
