<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nargpyqxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nargpyqxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:brand-home-assistant" {...props}></Icon>
