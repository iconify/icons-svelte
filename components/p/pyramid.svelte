<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg640xb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rg640xb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pyramid" {...props}></Icon>
