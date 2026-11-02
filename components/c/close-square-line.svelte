<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duv425vuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duv425vuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-square-line" {...props}></Icon>
