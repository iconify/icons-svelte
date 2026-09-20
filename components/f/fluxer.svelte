<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p80c_5d6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p80c_5d6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fluxer" {...props}></Icon>
