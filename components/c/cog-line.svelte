<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c64wkyboh.css';
import '../../css/a/az06ycclz.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="c64wkyboh clr-i-outline clr-i-outline-path-1"/><path class="az06ycclz clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:cog-line" {...props}></Icon>
