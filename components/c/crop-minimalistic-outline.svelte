<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wygv-re1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wygv-re1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crop-minimalistic-outline" {...props}></Icon>
