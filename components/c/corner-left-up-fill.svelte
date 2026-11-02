<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grf4x6b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grf4x6b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-left-up-fill" {...props}></Icon>
