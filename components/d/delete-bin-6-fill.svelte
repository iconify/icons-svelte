<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e882zy72m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e882zy72m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-6-fill" {...props}></Icon>
