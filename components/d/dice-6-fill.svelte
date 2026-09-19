<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-fpwoyhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s-fpwoyhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dice-6-fill" {...props}></Icon>
