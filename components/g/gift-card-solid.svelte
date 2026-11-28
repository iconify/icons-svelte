<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e051ewb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e051ewb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gift-card-solid" {...props}></Icon>
