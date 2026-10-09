<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qed_rfbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qed_rfbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-justify-20-bold" {...props}></Icon>
