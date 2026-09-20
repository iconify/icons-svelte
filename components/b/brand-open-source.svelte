<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruq-cxb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruq-cxb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-open-source" {...props}></Icon>
