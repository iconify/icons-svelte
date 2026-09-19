<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eob_xeb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eob_xeb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ok-finger" {...props}></Icon>
