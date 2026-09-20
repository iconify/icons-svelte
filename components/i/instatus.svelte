<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw309mb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw309mb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:instatus" {...props}></Icon>
