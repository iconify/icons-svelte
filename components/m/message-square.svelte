<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moxj19q1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moxj19q1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-square" {...props}></Icon>
