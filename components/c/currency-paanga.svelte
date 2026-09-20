<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlk993f9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlk993f9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-paanga" {...props}></Icon>
