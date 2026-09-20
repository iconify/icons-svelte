<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhdr_7b8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhdr_7b8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dts" {...props}></Icon>
