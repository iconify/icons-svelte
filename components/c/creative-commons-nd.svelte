<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyt30g5bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyt30g5bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:creative-commons-nd" {...props}></Icon>
