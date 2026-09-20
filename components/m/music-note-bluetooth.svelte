<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9zyacbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9zyacbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-bluetooth" {...props}></Icon>
