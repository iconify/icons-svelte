<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8v4adbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8v4adbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:menu-right" {...props}></Icon>
