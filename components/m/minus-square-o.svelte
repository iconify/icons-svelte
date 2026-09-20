<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/antp0sy-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="antp0sy-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:minus-square-o" {...props}></Icon>
