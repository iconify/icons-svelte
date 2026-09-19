<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x45u8ng5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x45u8ng5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-star-filled" {...props}></Icon>
