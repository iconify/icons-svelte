<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijyw3xq-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijyw3xq-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:map-marker-slash" {...props}></Icon>
