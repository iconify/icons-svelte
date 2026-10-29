<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg_u_wy3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_u_wy3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-bottom-solid" {...props}></Icon>
