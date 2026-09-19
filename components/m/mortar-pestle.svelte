<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsnadd_up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsnadd_up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mortar-pestle" {...props}></Icon>
