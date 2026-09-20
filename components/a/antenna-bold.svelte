<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta4gnrc5z.css';
import '../../css/n/ncb98mbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta4gnrc5z"/><path class="ncb98mbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:antenna-bold" {...props}></Icon>
