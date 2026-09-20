<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ixelbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_ixelbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-waves" {...props}></Icon>
