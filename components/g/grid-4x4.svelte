<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vef-s7bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vef-s7bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grid-4x4" {...props}></Icon>
