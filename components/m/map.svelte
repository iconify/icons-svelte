<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py-lk14be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py-lk14be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map" {...props}></Icon>
