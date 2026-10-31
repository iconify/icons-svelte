<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt_2hzb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt_2hzb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-round" {...props}></Icon>
