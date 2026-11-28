<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ijpj_lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d2ijpj_lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:geyser" {...props}></Icon>
