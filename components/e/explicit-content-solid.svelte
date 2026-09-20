<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go2_u_qmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go2_u_qmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:explicit-content-solid" {...props}></Icon>
