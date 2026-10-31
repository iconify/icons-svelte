<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6my62buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6my62buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hard-drive-round" {...props}></Icon>
