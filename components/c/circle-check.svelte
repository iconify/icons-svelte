<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmk826btk.css';
import '../../css/j/jpdwis9wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="jpdwis9wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:circle-check" {...props}></Icon>
