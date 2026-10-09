<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx9_9iq6d.css';
import '../../css/e/eumf_hb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lx9_9iq6d"/><path class="eumf_hb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-20-bold" {...props}></Icon>
