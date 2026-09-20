<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxzxubb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxzxubb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dashboard-4-fill" {...props}></Icon>
