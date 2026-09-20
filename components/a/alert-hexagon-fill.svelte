<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_r4d6d1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z_r4d6d1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-hexagon-fill" {...props}></Icon>
