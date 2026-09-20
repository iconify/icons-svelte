<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miehgxb5z.css';
import '../../css/e/ekhn6xp0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miehgxb5z"/><path class="ekhn6xp0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:photo-album-2-line" {...props}></Icon>
