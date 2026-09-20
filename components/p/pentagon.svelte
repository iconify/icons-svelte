<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew5er1t7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew5er1t7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pentagon" {...props}></Icon>
