<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yciimpb-x.css';
import '../../css/o/o0a-r_1pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yciimpb-x"/><path class="o0a-r_1pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-music-line" {...props}></Icon>
