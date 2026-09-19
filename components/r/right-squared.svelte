<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj8hzfb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hj8hzfb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:right-squared" {...props}></Icon>
