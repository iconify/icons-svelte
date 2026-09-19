<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmk826btk.css';
import '../../css/n/nd2uznbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="nd2uznbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:aim" {...props}></Icon>
