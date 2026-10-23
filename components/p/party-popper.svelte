<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy0_5uk2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy0_5uk2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:party-popper" {...props}></Icon>
