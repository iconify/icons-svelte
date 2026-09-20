<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y029h9jjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y029h9jjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fat-arrow-down-right" {...props}></Icon>
