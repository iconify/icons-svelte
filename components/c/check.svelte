<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm_ymtxnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_ymtxnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:check" {...props}></Icon>
