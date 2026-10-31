<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aejdy5bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aejdy5bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:door-round" {...props}></Icon>
