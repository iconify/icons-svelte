<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv654bc7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv654bc7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:forum-filled" {...props}></Icon>
