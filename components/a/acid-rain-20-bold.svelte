<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmpbyzcwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmpbyzcwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acid-rain-20-bold" {...props}></Icon>
