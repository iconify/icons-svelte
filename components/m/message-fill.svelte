<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f--pn5glr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f--pn5glr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-fill" {...props}></Icon>
