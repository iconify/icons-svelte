<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewdd1g-qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ewdd1g-qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brackets-20-bold" {...props}></Icon>
