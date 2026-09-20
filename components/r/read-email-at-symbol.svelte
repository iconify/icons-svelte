<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqao3fb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqao3fb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:read-email-at-symbol" {...props}></Icon>
