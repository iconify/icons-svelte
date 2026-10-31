<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8vpoib8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8vpoib8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-close-round" {...props}></Icon>
