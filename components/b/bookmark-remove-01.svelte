<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu6vqt9py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6vqt9py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-remove-01" {...props}></Icon>
