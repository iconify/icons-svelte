<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-yxi3umn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-yxi3umn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-from-line" {...props}></Icon>
