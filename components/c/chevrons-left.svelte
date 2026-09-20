<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt--3pvpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt--3pvpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-left" {...props}></Icon>
