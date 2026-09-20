<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbjpkzfay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbjpkzfay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-forward-circle" {...props}></Icon>
