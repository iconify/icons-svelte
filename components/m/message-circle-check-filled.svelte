<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7lwjkbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7lwjkbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-check-filled" {...props}></Icon>
