<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n17e6j3vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n17e6j3vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-down-circle-fill" {...props}></Icon>
