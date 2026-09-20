<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px9-5bcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px9-5bcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-height-fill" {...props}></Icon>
