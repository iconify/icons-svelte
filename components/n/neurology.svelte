<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgwm9obwk.css';
import '../../css/j/jsygb7bfs.css';
import '../../css/n/npgqhk_3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vgwm9obwk"/><path class="jsygb7bfs"/><path class="npgqhk_3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:neurology" {...props}></Icon>
