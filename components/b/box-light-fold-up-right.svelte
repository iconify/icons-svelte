<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0gygpb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h0gygpb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-fold-up-right" {...props}></Icon>
