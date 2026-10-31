<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wljf69bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wljf69bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-5-duotone-round" {...props}></Icon>
