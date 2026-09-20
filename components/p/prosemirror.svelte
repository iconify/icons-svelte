<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm535xbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm535xbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:prosemirror" {...props}></Icon>
