<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2jfklm1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j2jfklm1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:head-side-cough" {...props}></Icon>
