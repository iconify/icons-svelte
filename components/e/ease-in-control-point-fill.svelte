<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp_nfnigp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp_nfnigp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-control-point-fill" {...props}></Icon>
