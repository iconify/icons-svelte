<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q92jog0yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q92jog0yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:credit-card-2-back-fill" {...props}></Icon>
