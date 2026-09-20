<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no3v9abqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="no3v9abqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:live-video-remix" {...props}></Icon>
