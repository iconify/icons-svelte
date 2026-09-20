<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn2gtrrvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xn2gtrrvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:floor-lamp-minimalistic-outline" {...props}></Icon>
