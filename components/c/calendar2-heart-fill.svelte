<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2yqzbbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i2yqzbbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-heart-fill" {...props}></Icon>
