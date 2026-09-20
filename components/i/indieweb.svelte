<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeuyv8bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeuyv8bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:indieweb" {...props}></Icon>
