<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oivgnxbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oivgnxbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:baseball-solid" {...props}></Icon>
