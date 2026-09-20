<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec9i80skt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec9i80skt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-z" {...props}></Icon>
