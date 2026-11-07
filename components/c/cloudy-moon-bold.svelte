<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo2tsbqu.css';
import '../../css/n/n00rjyr1l.css';
import '../../css/m/m0ls1dbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfo2tsbqu"/><path class="n00rjyr1l"/><path class="m0ls1dbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloudy-moon-bold" {...props}></Icon>
