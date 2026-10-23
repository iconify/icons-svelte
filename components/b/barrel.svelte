<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li3m1bnbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li3m1bnbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:barrel" {...props}></Icon>
