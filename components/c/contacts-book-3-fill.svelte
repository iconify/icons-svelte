<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw4l2odzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw4l2odzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-3-fill" {...props}></Icon>
