<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2xkvt2tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2xkvt2tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:dice-5-fill" {...props}></Icon>
