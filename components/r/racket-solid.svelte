<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj2za5ydl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj2za5ydl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:racket-solid" {...props}></Icon>
