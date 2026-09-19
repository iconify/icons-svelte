<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuj6embez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuj6embez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:android" {...props}></Icon>
