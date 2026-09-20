<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si1cdrbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si1cdrbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aerial-lift-fill" {...props}></Icon>
