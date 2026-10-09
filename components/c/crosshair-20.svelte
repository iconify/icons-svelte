<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb1oskbsf.css';
import '../../css/e/eu4b83byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mb1oskbsf"/><path class="eu4b83byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crosshair-20" {...props}></Icon>
