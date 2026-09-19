<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avk0e-lpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avk0e-lpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:brush-outline" {...props}></Icon>
