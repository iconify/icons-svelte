<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzl_nd--g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzl_nd--g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:cast" {...props}></Icon>
