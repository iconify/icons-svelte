<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux3isacaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux3isacaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-gloss" {...props}></Icon>
