<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpfbl0bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dpfbl0bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-20" {...props}></Icon>
