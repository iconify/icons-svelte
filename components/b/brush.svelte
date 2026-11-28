<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq_8b3o-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq_8b3o-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:brush" {...props}></Icon>
