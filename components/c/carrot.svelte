<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6e890s2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e6e890s2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:carrot" {...props}></Icon>
