<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2n-ljuwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2n-ljuwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:play-circle" {...props}></Icon>
