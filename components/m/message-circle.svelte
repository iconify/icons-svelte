<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmx_o5b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmx_o5b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle" {...props}></Icon>
