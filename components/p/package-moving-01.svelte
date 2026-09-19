<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-jqw2ahc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-jqw2ahc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-moving-01" {...props}></Icon>
