<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejeoy_boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ejeoy_boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:post-11" {...props}></Icon>
