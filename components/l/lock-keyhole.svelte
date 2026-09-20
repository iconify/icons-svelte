<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_eoek3fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_eoek3fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lock-keyhole" {...props}></Icon>
