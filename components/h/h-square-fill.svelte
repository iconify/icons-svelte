<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t935cfbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t935cfbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:h-square-fill" {...props}></Icon>
