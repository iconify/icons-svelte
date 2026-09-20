<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne9la_bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne9la_bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:capsule-filled" {...props}></Icon>
