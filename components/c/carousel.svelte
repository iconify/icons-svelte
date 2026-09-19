<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr5kwbc1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr5kwbc1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:carousel" {...props}></Icon>
