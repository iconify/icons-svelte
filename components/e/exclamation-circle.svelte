<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1e3frofp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1e3frofp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exclamation-circle" {...props}></Icon>
