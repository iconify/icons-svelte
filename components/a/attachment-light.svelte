<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6y-zb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly6y-zb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attachment-light" {...props}></Icon>
