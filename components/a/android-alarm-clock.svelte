<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2w7lwbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2w7lwbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-alarm-clock" {...props}></Icon>
