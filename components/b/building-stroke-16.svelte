<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as14hklrl.css';
import '../../css/x/x-r-buvun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="as14hklrl"/><path class="x-r-buvun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:building-stroke-16" {...props}></Icon>
