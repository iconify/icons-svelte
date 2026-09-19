<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shan8t4to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shan8t4to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dazn" {...props}></Icon>
