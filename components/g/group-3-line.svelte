<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgb_9abwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgb_9abwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:group-3-line" {...props}></Icon>
