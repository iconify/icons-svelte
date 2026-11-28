<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy8_od6wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy8_od6wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-star" {...props}></Icon>
