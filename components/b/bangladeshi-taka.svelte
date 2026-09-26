<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf2i7pbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2i7pbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bangladeshi-taka" {...props}></Icon>
