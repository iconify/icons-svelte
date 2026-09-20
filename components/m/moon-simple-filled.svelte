<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvfa_t.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvfa_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:moon-simple-filled" {...props}></Icon>
