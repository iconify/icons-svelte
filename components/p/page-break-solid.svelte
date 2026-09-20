<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyc56ubjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oyc56ubjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:page-break-solid" {...props}></Icon>
