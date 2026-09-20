<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyg9p_u_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyg9p_u_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-system-update" {...props}></Icon>
