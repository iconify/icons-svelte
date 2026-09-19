<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aer23ob0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aer23ob0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-left-04" {...props}></Icon>
