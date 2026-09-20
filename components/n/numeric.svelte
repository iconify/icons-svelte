<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f31f9vmdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f31f9vmdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric" {...props}></Icon>
