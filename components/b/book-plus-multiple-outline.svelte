<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbucz-2oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbucz-2oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-plus-multiple-outline" {...props}></Icon>
