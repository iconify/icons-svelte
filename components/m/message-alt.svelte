<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0fcgjs6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0fcgjs6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:message-alt" {...props}></Icon>
