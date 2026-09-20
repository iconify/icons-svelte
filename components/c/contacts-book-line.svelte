<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkrd5vafu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkrd5vafu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-line" {...props}></Icon>
