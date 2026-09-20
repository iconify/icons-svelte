<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e634_5b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="e634_5b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-fold-down-right" {...props}></Icon>
