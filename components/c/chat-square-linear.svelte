<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dom1d86ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dom1d86ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-linear" {...props}></Icon>
