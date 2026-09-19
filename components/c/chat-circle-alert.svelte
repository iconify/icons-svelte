<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4ghhtb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4ghhtb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-alert" {...props}></Icon>
