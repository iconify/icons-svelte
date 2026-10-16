<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i00v-b3kp.css';
import '../../css/c/cj81ctblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i00v-b3kp"/><path class="cj81ctblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-left-close-20-bold" {...props}></Icon>
