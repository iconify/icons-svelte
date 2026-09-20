<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu3pacbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu3pacbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-latin" {...props}></Icon>
