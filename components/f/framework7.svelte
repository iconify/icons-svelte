<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_oeyvb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_oeyvb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:framework7" {...props}></Icon>
