<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyfm_1-bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyfm_1-bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-n" {...props}></Icon>
