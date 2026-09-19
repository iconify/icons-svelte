<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-nanhbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-nanhbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-up-md" {...props}></Icon>
