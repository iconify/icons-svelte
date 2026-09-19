<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8pd91bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u8pd91bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:display" {...props}></Icon>
