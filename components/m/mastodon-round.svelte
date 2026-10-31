<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkvlvwbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkvlvwbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mastodon-round" {...props}></Icon>
