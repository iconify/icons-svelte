<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw6ehvpzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw6ehvpzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:chat-info" {...props}></Icon>
