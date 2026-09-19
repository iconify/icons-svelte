<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saxxmztwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="saxxmztwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reader" {...props}></Icon>
