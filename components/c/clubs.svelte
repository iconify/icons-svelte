<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lki5-vbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lki5-vbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clubs" {...props}></Icon>
