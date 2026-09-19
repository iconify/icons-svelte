<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlvpvna1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mlvpvna1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-x-fill" {...props}></Icon>
