<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogqs7wb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqs7wb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-solid" {...props}></Icon>
