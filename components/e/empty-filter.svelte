<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq32jab3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sq32jab3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:empty-filter" {...props}></Icon>
