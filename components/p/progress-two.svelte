<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el0eubbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="el0eubbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:progress-two" {...props}></Icon>
