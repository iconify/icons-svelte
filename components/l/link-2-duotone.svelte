<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryzlypbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ryzlypbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:link-2-duotone" {...props}></Icon>
