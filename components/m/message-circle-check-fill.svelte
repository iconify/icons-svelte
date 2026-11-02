<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k271hvb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k271hvb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-check-fill" {...props}></Icon>
