<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8iiln-of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8iiln-of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kit" {...props}></Icon>
