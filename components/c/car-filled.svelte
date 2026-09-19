<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px0hoobzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px0hoobzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:car-filled" {...props}></Icon>
