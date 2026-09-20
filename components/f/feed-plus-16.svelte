<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv5evy_iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cv5evy_iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-plus-16" {...props}></Icon>
