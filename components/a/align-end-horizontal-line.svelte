<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n70tk6bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n70tk6bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-end-horizontal-line" {...props}></Icon>
