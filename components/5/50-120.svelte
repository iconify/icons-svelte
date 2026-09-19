<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7qxp_zpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="w7qxp_zpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:50-120" {...props}></Icon>
