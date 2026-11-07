<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu07wd4oe.css';
import '../../css/j/j7xw_esfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu07wd4oe"/><path clip-rule="evenodd" class="j7xw_esfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-chat-bold" {...props}></Icon>
