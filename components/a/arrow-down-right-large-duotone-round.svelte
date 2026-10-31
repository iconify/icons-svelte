<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csk8wdbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csk8wdbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-right-large-duotone-round" {...props}></Icon>
