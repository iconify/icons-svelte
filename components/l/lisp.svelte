<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr10uwbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jr10uwbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lisp" {...props}></Icon>
