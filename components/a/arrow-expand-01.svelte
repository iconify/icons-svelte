<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzihj1__f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzihj1__f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-expand-01" {...props}></Icon>
