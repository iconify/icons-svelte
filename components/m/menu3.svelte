<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j49n-pbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":16};
const content = `<path class="j49n-pbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:menu3" {...props}></Icon>
