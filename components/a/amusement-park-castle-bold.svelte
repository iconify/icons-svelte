<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhxnwmbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxnwmbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:amusement-park-castle-bold" {...props}></Icon>
