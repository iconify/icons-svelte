<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqd9lkg8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqd9lkg8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message-circle-filled" {...props}></Icon>
