<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og4e6_85k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og4e6_85k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roller-shade" {...props}></Icon>
