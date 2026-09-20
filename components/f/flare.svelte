<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn2ms_bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn2ms_bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:flare" {...props}></Icon>
