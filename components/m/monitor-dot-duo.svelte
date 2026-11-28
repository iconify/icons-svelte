<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-kr0zbkh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zo3r5sxxk.css';
import '../../css/m/mn3u620zx.css';
import '../../css/x/xd8yd0bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-kr0zbkh secondary"/><g class="dt0cm9dhy primary"><path class="zo3r5sxxk"/><path class="mn3u620zx"/><path class="xd8yd0bhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-dot-duo" {...props}></Icon>
