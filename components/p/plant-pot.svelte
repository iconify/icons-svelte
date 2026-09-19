<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx84ycc3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx84ycc3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plant-pot" {...props}></Icon>
