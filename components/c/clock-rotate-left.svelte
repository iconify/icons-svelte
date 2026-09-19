<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6maa3bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6maa3bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clock-rotate-left" {...props}></Icon>
