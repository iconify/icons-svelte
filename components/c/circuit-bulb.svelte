<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvw_drbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvw_drbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-bulb" {...props}></Icon>
