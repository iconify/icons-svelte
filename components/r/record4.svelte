<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to4no2b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to4no2b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:record4" {...props}></Icon>
