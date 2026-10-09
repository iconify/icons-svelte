<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irlkbhb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="irlkbhb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:resistor-48" {...props}></Icon>
