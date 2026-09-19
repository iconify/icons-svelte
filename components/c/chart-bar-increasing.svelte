<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y78neubqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y78neubqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-bar-increasing" {...props}></Icon>
