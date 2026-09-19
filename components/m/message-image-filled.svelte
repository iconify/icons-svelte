<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivom5o5ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivom5o5ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-image-filled" {...props}></Icon>
