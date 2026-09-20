<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfsh_ybmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfsh_ybmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-ring-light" {...props}></Icon>
