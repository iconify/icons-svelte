<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny92bacsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ny92bacsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:gate" {...props}></Icon>
