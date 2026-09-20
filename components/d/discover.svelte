<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbup0b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppbup0b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:discover" {...props}></Icon>
