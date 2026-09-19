<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw6aov9hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nw6aov9hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-up" {...props}></Icon>
