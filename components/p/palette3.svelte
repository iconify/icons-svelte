<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyn-ddc_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyn-ddc_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:palette3" {...props}></Icon>
