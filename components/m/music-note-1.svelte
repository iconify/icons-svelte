<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs9hhccab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs9hhccab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:music-note-1" {...props}></Icon>
