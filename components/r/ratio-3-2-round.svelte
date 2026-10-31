<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7gafosax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7gafosax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ratio-3-2-round" {...props}></Icon>
