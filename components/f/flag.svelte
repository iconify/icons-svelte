<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke23d28rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ke23d28rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:flag" {...props}></Icon>
