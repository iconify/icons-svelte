<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goa68fb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goa68fb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-framer" {...props}></Icon>
