<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8g8qlfld.css';
import '../../css/a/a50et0bgu.css';
import '../../css/q/q-6bg4l5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8g8qlfld"/><path class="a50et0bgu"/><path class="q-6bg4l5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:edit" {...props}></Icon>
