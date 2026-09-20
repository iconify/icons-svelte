<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svq151qyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svq151qyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mastodon-line" {...props}></Icon>
