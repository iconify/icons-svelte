<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qafr6ubam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qafr6ubam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:align-vertical-center" {...props}></Icon>
