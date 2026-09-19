<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ladw2kb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ladw2kb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:ringer-off" {...props}></Icon>
