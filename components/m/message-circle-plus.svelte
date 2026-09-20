<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikjp-dbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikjp-dbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle-plus" {...props}></Icon>
