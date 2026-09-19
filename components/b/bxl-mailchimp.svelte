<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jotj3v2bz.css';
import '../../css/y/y_-ddrbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jotj3v2bz"/><path class="y_-ddrbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-mailchimp" {...props}></Icon>
