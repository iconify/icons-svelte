<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft3fdyb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft3fdyb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-minus-fill-round" {...props}></Icon>
