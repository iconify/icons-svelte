<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfempqb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zfempqb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-notch-duotone" {...props}></Icon>
