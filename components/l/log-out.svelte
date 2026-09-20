<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enuv-esbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enuv-esbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:log-out" {...props}></Icon>
