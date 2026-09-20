<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfv7x8bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfv7x8bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:package-variant-subtract" {...props}></Icon>
