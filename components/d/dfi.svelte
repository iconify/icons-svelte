<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tksyfselm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tksyfselm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dfi" {...props}></Icon>
