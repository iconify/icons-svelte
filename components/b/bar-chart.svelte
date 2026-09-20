<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpbrlabrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cpbrlabrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:bar-chart" {...props}></Icon>
