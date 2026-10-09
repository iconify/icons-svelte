<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d381xzbzn.css';
import '../../css/s/sethd29la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d381xzbzn"/><path class="sethd29la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gear-20" {...props}></Icon>
