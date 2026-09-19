<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep6yosbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6yosbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:play" {...props}></Icon>
