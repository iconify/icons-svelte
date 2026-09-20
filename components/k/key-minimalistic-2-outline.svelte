<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g36q7nb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g36q7nb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-2-outline" {...props}></Icon>
