<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5diqgc_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5diqgc_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tesla" {...props}></Icon>
