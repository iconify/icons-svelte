<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tip2o2__i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tip2o2__i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dungeon" {...props}></Icon>
