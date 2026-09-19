<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lodq44bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lodq44bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ios-face-recognition" {...props}></Icon>
