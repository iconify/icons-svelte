<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbp3mj2bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbp3mj2bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bing-logo-1-block" {...props}></Icon>
