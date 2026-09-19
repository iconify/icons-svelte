<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6qay1xjw.css';
import '../../css/q/qutfy0qah.css';
import '../../css/y/yj4j86lvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="s6qay1xjw"/><path class="qutfy0qah"/><path class="yj4j86lvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-rotary-first-right-filled" {...props}></Icon>
