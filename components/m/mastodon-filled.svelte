<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj8y-ybio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj8y-ybio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mastodon-filled" {...props}></Icon>
