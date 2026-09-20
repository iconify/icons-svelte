<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwvch8b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwvch8b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opencode" {...props}></Icon>
