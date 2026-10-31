<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojcapjb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojcapjb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:contrast-fill-round" {...props}></Icon>
