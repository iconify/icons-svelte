<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o523_9btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o523_9btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-empty-solid" {...props}></Icon>
