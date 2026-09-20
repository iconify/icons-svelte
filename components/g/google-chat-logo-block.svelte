<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvzh4z13o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvzh4z13o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-chat-logo-block" {...props}></Icon>
