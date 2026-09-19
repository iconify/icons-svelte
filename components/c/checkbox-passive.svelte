<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy_iv7ssp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="oy_iv7ssp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:checkbox-passive" {...props}></Icon>
