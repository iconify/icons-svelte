<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy8l88k7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy8l88k7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-remove-02" {...props}></Icon>
