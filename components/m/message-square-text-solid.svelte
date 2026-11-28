<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/raqhdr7fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="raqhdr7fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-text-solid" {...props}></Icon>
