<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7srk4lqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w7srk4lqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:lock-locked" {...props}></Icon>
