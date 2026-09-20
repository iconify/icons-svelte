<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elbbp9siz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elbbp9siz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mini-blinds" {...props}></Icon>
