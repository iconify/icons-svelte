<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6kw6_7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tt6kw6_7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:mail-o" {...props}></Icon>
