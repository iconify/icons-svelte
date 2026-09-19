<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe0cwd_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe0cwd_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-2" {...props}></Icon>
