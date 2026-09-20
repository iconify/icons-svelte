<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_jewnre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mj_jewnre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:blackboard" {...props}></Icon>
