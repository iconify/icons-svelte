<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igi0b0bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="igi0b0bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:italic-e" {...props}></Icon>
