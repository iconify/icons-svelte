<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysdv8ccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysdv8ccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:octagon-plus" {...props}></Icon>
