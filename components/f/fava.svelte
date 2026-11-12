<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yktm7h6-w.css';
import '../../css/j/jyold6wus.css';
import '../../css/b/b671z779q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yktm7h6-w"/><path class="jyold6wus"/><path class="b671z779q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fava" {...props}></Icon>
