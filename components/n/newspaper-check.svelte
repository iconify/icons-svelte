<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lllxgebsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lllxgebsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:newspaper-check" {...props}></Icon>
