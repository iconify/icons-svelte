<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc5evijpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wc5evijpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:credit-card" {...props}></Icon>
