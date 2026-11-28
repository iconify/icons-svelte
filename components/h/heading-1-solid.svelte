<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtyclizma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtyclizma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-1-solid" {...props}></Icon>
