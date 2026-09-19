<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr50xn6_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pr50xn6_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:angle" {...props}></Icon>
