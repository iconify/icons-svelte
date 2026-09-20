<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9a0wu13y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9a0wu13y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:daze-solid" {...props}></Icon>
