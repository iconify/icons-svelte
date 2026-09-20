<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u41rktw1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u41rktw1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:globe" {...props}></Icon>
