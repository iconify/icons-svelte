<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tphv1z1vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tphv1z1vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:high-temperature-fill" {...props}></Icon>
