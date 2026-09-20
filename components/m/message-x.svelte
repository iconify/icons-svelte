<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd82nybwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd82nybwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-x" {...props}></Icon>
