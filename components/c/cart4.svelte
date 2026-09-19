<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo2c-_rnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo2c-_rnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart4" {...props}></Icon>
