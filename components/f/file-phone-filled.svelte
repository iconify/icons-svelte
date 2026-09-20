<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv10nottr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv10nottr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:file-phone-filled" {...props}></Icon>
