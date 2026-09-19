<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajr6vqxuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ajr6vqxuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mars-double" {...props}></Icon>
