<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arjspos7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arjspos7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-check-filled" {...props}></Icon>
