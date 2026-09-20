<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8vdr063m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8vdr063m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonmusic" {...props}></Icon>
