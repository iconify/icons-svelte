<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs_2dcbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bs_2dcbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:1-square-fill" {...props}></Icon>
