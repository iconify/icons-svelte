<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgfqs0b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgfqs0b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cookie-fill-round" {...props}></Icon>
