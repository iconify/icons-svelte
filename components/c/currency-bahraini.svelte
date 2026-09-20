<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5uw44bjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5uw44bjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-bahraini" {...props}></Icon>
