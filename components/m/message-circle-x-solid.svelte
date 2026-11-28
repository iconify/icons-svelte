<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl1ouqb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl1ouqb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-x-solid" {...props}></Icon>
