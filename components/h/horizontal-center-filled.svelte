<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhjwkd_5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhjwkd_5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-center-filled" {...props}></Icon>
