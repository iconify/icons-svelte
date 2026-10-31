<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0brvyb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0brvyb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-4-3-fill-round" {...props}></Icon>
