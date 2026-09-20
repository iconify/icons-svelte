<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yasmj2z1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yasmj2z1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox" {...props}></Icon>
