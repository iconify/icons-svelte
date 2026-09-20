<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wae83hbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wae83hbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flag-2-linear" {...props}></Icon>
