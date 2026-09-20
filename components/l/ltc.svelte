<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7mof65cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7mof65cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ltc" {...props}></Icon>
