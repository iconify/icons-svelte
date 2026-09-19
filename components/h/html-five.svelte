<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na37jlbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="na37jlbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:html-five" {...props}></Icon>
