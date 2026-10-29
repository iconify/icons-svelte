<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1v28kbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1v28kbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-axis-3d" {...props}></Icon>
