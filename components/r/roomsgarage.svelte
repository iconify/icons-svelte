<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laq0t2bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laq0t2bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomsgarage" {...props}></Icon>
