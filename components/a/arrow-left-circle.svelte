<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/envzjuxhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="envzjuxhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-left-circle" {...props}></Icon>
