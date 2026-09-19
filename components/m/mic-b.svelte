<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6-4xurgn.css';
import '../../css/a/am0up7b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6-4xurgn"/><path class="am0up7b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-b" {...props}></Icon>
