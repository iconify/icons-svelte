<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-mq8obmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-mq8obmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cogwheel" {...props}></Icon>
