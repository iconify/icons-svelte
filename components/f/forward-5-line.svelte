<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq5f9sn3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5f9sn3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-5-line" {...props}></Icon>
