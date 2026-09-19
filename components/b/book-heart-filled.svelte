<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tibjlubtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tibjlubtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-heart-filled" {...props}></Icon>
