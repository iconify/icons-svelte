<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnksxrbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1216,"height":1312};
const content = `<path class="lnksxrbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:close" {...props}></Icon>
