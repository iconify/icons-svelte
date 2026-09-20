<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec-wklb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec-wklb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lamp" {...props}></Icon>
