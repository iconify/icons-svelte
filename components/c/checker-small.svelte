<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqh3q-bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vqh3q-bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checker-small" {...props}></Icon>
