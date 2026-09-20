<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-ttlzbrv.css';
import '../../css/w/woppo0l-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ttlzbrv"/><path class="woppo0l-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:inbox" {...props}></Icon>
