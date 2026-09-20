<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrhzn-qkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrhzn-qkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-circle-r-line" {...props}></Icon>
