<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs11mzbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs11mzbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rainbow-fill" {...props}></Icon>
