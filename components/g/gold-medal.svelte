<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iojc3c5mq.css';
import '../../css/h/h-mv3pyqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iojc3c5mq"/><path class="h-mv3pyqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:gold-medal" {...props}></Icon>
