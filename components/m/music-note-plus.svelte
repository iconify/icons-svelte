<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6sjh55au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6sjh55au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:music-note-plus" {...props}></Icon>
