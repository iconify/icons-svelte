<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geqsfhbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geqsfhbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cellphone-basic" {...props}></Icon>
