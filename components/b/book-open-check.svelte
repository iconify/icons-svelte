<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix285gbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix285gbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-open-check" {...props}></Icon>
