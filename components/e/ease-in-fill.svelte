<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa4_z_bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4_z_bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-fill" {...props}></Icon>
