<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb1w2tbur.css';
import '../../css/e/ejx2y1bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb1w2tbur"/><path class="ejx2y1bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-snowfall-bold-duotone" {...props}></Icon>
