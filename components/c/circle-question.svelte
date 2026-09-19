<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqyr3mqxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqyr3mqxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-question" {...props}></Icon>
