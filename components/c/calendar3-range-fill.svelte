<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfotcudyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lfotcudyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar3-range-fill" {...props}></Icon>
