<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4i1geb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4i1geb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:channel-4-uk" {...props}></Icon>
