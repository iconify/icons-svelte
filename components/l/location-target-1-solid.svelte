<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q66_a9bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q66_a9bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:location-target-1-solid" {...props}></Icon>
