<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lam3n-0ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lam3n-0ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:night" {...props}></Icon>
