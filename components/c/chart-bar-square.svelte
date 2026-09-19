<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs2qkn-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs2qkn-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chart-bar-square" {...props}></Icon>
