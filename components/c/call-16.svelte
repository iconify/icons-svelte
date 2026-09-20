<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckwu9ub3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ckwu9ub3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-16" {...props}></Icon>
