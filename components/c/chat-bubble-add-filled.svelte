<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdoap5bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdoap5bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-add-filled" {...props}></Icon>
