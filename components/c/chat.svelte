<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c26h3kbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c26h3kbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chat" {...props}></Icon>
