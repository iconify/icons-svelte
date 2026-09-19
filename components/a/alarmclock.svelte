<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng3rv4n5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ng3rv4n5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alarmclock" {...props}></Icon>
