<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9aylmbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9aylmbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-minus-filled" {...props}></Icon>
