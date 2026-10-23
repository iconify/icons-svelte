<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bue59f0bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bue59f0bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bookmark-off" {...props}></Icon>
