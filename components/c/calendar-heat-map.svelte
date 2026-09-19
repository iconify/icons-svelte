<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpyx0diih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cpyx0diih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calendar-heat-map" {...props}></Icon>
