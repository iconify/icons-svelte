<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1-eh7tkj.css';
import '../../css/j/jdu6zub5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-eh7tkj"/><path clip-rule="evenodd" class="jdu6zub5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:plex" {...props}></Icon>
