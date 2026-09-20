<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_jp9ebst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_jp9ebst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:laptop" {...props}></Icon>
