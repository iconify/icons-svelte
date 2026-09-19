<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x71ga5btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x71ga5btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:menu-button-wide-fill" {...props}></Icon>
