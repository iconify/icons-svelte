<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7kqcoj9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":653};
const content = `<path class="v7kqcoj9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:menu" {...props}></Icon>
