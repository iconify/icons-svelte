<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrlmcobho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrlmcobho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:map-minus" {...props}></Icon>
