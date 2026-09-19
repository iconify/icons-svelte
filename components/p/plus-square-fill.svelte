<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-nfe_bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l-nfe_bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus-square-fill" {...props}></Icon>
