<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj_mhsbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj_mhsbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perfecto" {...props}></Icon>
