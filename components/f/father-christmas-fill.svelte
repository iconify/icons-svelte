<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdr35o1ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdr35o1ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:father-christmas-fill" {...props}></Icon>
