<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fedupdbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fedupdbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-right" {...props}></Icon>
