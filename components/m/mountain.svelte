<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urw_vubil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urw_vubil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mountain" {...props}></Icon>
