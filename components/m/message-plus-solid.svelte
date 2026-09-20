<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7lg59b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7lg59b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-plus-solid" {...props}></Icon>
