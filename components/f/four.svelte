<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z69k53r8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z69k53r8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:four" {...props}></Icon>
