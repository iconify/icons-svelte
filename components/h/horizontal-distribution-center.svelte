<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt1h73gnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt1h73gnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:horizontal-distribution-center" {...props}></Icon>
