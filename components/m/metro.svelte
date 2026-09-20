<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im0wz2aiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im0wz2aiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:metro" {...props}></Icon>
