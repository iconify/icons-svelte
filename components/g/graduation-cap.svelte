<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc_dccbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc_dccbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:graduation-cap" {...props}></Icon>
