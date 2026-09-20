<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfdhb-19z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfdhb-19z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-right-bottom-corner-3" {...props}></Icon>
