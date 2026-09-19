<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv8z3-74d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":697,"height":768};
const content = `<path class="yv8z3-74d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:coffee" {...props}></Icon>
