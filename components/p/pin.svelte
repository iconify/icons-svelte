<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2x01abpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b2x01abpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:pin" {...props}></Icon>
