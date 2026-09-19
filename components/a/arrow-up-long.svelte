<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3vuzjkvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y3vuzjkvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-long" {...props}></Icon>
