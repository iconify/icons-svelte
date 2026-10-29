<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b01t7_bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b01t7_bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-desk-solid" {...props}></Icon>
