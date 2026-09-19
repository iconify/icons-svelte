<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj0h9ub6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj0h9ub6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-check-filled" {...props}></Icon>
