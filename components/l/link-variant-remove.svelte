<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my-q2jn-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my-q2jn-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-variant-remove" {...props}></Icon>
