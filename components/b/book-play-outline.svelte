<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbc9jmbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbc9jmbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-play-outline" {...props}></Icon>
