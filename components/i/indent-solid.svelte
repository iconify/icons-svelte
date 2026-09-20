<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u67g4cbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u67g4cbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-solid" {...props}></Icon>
