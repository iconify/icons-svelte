<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1d4eejru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1d4eejru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:knife-blood-line" {...props}></Icon>
