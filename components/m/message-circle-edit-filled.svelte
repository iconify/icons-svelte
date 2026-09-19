<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af3v4qk0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af3v4qk0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-edit-filled" {...props}></Icon>
