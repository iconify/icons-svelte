<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuc792mew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uuc792mew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:plugins-checked" {...props}></Icon>
