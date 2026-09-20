<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-f0xhbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-f0xhbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-left" {...props}></Icon>
