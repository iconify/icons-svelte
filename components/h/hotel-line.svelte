<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puwkpfzjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puwkpfzjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hotel-line" {...props}></Icon>
