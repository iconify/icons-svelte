<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r15gej7bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r15gej7bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:menu-up" {...props}></Icon>
