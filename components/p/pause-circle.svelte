<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wph9epb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wph9epb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pause-circle" {...props}></Icon>
