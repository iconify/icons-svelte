<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th_20f-bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th_20f-bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headset-off" {...props}></Icon>
