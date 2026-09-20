<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq7rhjatd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq7rhjatd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:blackberry" {...props}></Icon>
