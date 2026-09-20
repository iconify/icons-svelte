<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7b5obcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7b5obcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-corner-left-down-solid" {...props}></Icon>
