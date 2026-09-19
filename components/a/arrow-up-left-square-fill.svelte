<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uopsl9spe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uopsl9spe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-left-square-fill" {...props}></Icon>
