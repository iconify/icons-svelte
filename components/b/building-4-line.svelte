<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-0zxybod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-0zxybod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-4-line" {...props}></Icon>
