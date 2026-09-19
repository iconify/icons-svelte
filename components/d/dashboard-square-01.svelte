<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phqf06_-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phqf06_-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dashboard-square-01" {...props}></Icon>
