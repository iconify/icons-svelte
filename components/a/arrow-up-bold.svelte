<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpkwgyn6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qpkwgyn6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-bold" {...props}></Icon>
