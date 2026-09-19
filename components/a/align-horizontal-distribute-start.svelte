<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwb_-q86x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwb_-q86x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-distribute-start" {...props}></Icon>
