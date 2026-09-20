<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgo5f8b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo5f8b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-lines" {...props}></Icon>
