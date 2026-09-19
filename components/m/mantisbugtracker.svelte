<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr88xkbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="lr88xkbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mantisbugtracker" {...props}></Icon>
