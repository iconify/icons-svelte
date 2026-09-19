<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfjcb0b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjcb0b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:download-light" {...props}></Icon>
