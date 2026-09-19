<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqg5a0bzs.css';
import '../../css/d/dzfumybez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqg5a0bzs"/><path class="dzfumybez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:eye-off-outline" {...props}></Icon>
