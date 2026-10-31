<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deotjzbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deotjzbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heart-off-fill-round" {...props}></Icon>
