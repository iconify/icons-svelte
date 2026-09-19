<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yranhr-md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yranhr-md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-right-01" {...props}></Icon>
