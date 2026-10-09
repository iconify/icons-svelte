<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvwn6b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="odvwn6b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ai-sparkle-20-bold" {...props}></Icon>
