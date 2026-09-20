<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaphsqb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaphsqb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lira-waves-solid" {...props}></Icon>
