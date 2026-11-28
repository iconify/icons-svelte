<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqnh7lc1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqnh7lc1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:inbox-arrow-right" {...props}></Icon>
