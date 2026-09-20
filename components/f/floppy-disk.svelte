<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub5bnwn-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub5bnwn-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floppy-disk" {...props}></Icon>
