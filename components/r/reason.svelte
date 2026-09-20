<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy0upab9n.css';
import '../../css/l/lyrgvcbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vy0upab9n"/><path class="lyrgvcbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:reason" {...props}></Icon>
