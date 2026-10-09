<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4quabhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hw4quabhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-off-48" {...props}></Icon>
