<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x--dth1jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x--dth1jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pharmacy-filled" {...props}></Icon>
