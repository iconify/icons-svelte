<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiv_d-bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiv_d-bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roomsbalcony" {...props}></Icon>
