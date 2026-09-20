<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahbkc0wog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ahbkc0wog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fort" {...props}></Icon>
