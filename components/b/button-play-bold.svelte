<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyy0mledw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyy0mledw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:button-play-bold" {...props}></Icon>
