<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grm7v7f_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="grm7v7f_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:head-side-virus" {...props}></Icon>
