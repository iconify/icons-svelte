<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd9q9w1ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd9q9w1ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-terminator" {...props}></Icon>
