<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xce-k95br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xce-k95br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-l-filled" {...props}></Icon>
