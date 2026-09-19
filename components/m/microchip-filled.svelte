<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh60aydpi.css';
import '../../css/v/v_2n0eezf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="fh60aydpi"/><path class="v_2n0eezf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microchip-filled" {...props}></Icon>
