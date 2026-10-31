<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h76dexwai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h76dexwai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:book-open-bulk-round" {...props}></Icon>
