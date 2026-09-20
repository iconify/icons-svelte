<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecczycpjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecczycpjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-1-filled" {...props}></Icon>
