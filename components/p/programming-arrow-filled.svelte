<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urlgr2eji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urlgr2eji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:programming-arrow-filled" {...props}></Icon>
