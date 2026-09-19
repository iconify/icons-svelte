<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2n25kb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2n25kb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-heart-filled" {...props}></Icon>
