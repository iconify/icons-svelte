<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq-xok-8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uq-xok-8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:chemist-14" {...props}></Icon>
