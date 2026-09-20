<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub_ceubfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ub_ceubfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hollo-light" {...props}></Icon>
