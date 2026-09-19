<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxss0fhja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxss0fhja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path" {...props}></Icon>
