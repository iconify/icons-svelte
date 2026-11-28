<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eib0c1m0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eib0c1m0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pin-off" {...props}></Icon>
