<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h05ydob2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h05ydob2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:at-sign" {...props}></Icon>
