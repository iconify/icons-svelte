<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6lsn5bzb.css';
import '../../css/j/j2c1c4b4t.css';
import '../../css/p/pyhe_fr8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6lsn5bzb"/><path class="j2c1c4b4t"/><path class="pyhe_fr8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:retouch-face" {...props}></Icon>
