<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hane4bbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hane4bbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pin" {...props}></Icon>
