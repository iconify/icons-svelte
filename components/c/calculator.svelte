<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts1854bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ts1854bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:calculator" {...props}></Icon>
