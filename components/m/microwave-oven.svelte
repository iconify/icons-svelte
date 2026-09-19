<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd4zl64s.css';
import '../../css/w/w9yaz1b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd4zl64s"/><path class="w9yaz1b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microwave-oven" {...props}></Icon>
