<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw96g0b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sw96g0b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:llama-cpp-dark" {...props}></Icon>
