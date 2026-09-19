<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_f9w-laq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k_f9w-laq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cake-fill" {...props}></Icon>
