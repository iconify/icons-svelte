<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inje7ybsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inje7ybsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:priority-high-solid" {...props}></Icon>
