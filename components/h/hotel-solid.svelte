<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hki1y3bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hki1y3bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hotel-solid" {...props}></Icon>
