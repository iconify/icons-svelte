<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4cqtybrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y4cqtybrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:direct-current-20-bold" {...props}></Icon>
