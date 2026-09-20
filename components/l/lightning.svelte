<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlkvmfbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlkvmfbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lightning" {...props}></Icon>
