<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvedukegi.css';
import '../../css/d/db1dkebgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vvedukegi"/><path class="db1dkebgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-20-bold" {...props}></Icon>
