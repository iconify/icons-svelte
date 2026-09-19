<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhcvs-bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhcvs-bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dice-6" {...props}></Icon>
