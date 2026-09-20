<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_0inpd7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_0inpd7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chat-minus-solid" {...props}></Icon>
