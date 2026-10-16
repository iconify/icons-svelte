<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrw5zccqv.css';
import '../../css/g/gu_hyzqsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrw5zccqv"/><path class="gu_hyzqsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-star-48-bold" {...props}></Icon>
