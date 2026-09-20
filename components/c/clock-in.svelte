<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enhjo2bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enhjo2bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-in" {...props}></Icon>
