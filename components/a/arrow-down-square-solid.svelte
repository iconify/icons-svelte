<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h42s2v16e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h42s2v16e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-square-solid" {...props}></Icon>
