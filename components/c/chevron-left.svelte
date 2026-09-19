<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcz3a9bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcz3a9bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevron-left" {...props}></Icon>
