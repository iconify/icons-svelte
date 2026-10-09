<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-y598bgk.css';
import '../../css/c/cuw48wy1a.css';
import '../../css/u/u5cct483i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y-y598bgk"/><path class="cuw48wy1a"/><path class="u5cct483i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:record-player-20" {...props}></Icon>
