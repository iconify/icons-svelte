<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_kozj14v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="t_kozj14v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:bluetooth" {...props}></Icon>
