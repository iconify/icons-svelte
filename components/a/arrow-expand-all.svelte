<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_rw8yb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_rw8yb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-expand-all" {...props}></Icon>
