<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9-s-obyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9-s-obyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:layers-two" {...props}></Icon>
