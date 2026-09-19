<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x52iozflm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x52iozflm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-magnifying-glass" {...props}></Icon>
