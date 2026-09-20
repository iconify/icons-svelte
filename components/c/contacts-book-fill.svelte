<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l59qypbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l59qypbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-fill" {...props}></Icon>
