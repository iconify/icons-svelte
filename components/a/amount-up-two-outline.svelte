<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd8qvabnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cd8qvabnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-up-two-outline" {...props}></Icon>
