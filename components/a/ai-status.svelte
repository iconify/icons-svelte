<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/j/jjnq7107s.css';
import '../../css/l/l4qq16brp.css';
import '../../css/u/uyfynbbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="jjnq7107s"/><path class="l4qq16brp"/><path class="uyfynbbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-status" {...props}></Icon>
