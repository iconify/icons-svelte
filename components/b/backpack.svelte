<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfkxvpx_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfkxvpx_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:backpack" {...props}></Icon>
