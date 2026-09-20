<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d61wqdblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d61wqdblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:friends-feed-logo" {...props}></Icon>
