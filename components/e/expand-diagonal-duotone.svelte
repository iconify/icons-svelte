<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx2dvxl_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx2dvxl_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-diagonal-duotone" {...props}></Icon>
