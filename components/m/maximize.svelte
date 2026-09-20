<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e94gmx3je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e94gmx3je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:maximize" {...props}></Icon>
