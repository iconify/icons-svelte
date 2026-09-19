<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-1fm9-zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-1fm9-zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:documents" {...props}></Icon>
