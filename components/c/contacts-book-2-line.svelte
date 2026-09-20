<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1ulobon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx1ulobon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contacts-book-2-line" {...props}></Icon>
