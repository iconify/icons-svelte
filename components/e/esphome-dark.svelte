<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz5434rjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz5434rjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:esphome-dark" {...props}></Icon>
