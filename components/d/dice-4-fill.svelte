<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7fa9ebby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w7fa9ebby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dice-4-fill" {...props}></Icon>
