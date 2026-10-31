<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz_o64dij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz_o64dij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-sad-round" {...props}></Icon>
