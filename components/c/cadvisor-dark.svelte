<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tliz7ac4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tliz7ac4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cadvisor-dark" {...props}></Icon>
