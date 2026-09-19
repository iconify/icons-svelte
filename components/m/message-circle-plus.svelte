<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufqvjm-rq.css';
import '../../css/f/fu72iwgtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufqvjm-rq"/><path class="fu72iwgtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-plus" {...props}></Icon>
