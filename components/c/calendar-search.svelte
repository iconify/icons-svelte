<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2yt0tb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2yt0tb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-search" {...props}></Icon>
