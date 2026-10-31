<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgpg_wbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgpg_wbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-g-duocolor-round" {...props}></Icon>
