<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njcw9_wkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njcw9_wkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-open-fill-round" {...props}></Icon>
