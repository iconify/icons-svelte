<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymx_-ubor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymx_-ubor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beeper-light" {...props}></Icon>
