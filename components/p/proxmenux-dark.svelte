<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew05xgb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ew05xgb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxmenux-dark" {...props}></Icon>
