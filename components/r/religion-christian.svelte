<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlveijbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlveijbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:religion-christian" {...props}></Icon>
