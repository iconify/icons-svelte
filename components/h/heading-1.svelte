<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9oxuy4yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9oxuy4yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-1" {...props}></Icon>
