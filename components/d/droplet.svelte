<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqssqub7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="lqssqub7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:droplet" {...props}></Icon>
