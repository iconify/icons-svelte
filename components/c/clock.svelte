<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlr7fx0nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlr7fx0nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:clock" {...props}></Icon>
