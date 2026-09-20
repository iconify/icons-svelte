<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spzailqor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="spzailqor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-horizontal-right" {...props}></Icon>
