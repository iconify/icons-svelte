<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds-3ltbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds-3ltbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ban-gloss" {...props}></Icon>
