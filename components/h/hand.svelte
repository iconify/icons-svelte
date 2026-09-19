<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd7agbbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cd7agbbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand" {...props}></Icon>
