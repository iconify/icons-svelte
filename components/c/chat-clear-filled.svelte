<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh8vo1__v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh8vo1__v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-clear-filled" {...props}></Icon>
