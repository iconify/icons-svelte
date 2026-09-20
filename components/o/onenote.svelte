<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85t0r4ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f85t0r4ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:onenote" {...props}></Icon>
