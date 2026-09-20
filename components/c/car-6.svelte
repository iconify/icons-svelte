<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_g86w7hz.css';
import '../../css/v/v4k56rbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_g86w7hz"/><path class="v4k56rbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:car-6" {...props}></Icon>
