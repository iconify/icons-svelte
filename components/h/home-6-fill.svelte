<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki14_kbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki14_kbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-6-fill" {...props}></Icon>
