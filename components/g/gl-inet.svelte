<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq8gncb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq8gncb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gl-inet" {...props}></Icon>
