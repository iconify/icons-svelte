<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8h17jlhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c8h17jlhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:head-side-cough-slash" {...props}></Icon>
