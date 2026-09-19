<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amwavyihl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amwavyihl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-list" {...props}></Icon>
