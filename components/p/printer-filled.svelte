<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btgo_69aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btgo_69aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:printer-filled" {...props}></Icon>
