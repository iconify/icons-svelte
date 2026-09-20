<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psoeldpuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psoeldpuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hexo" {...props}></Icon>
