<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqfgsuczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqfgsuczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:piano-grand-fill" {...props}></Icon>
