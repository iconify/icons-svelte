<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu59abbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lu59abbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation-square-fill" {...props}></Icon>
