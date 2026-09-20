<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jonce8nkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jonce8nkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aries-fill" {...props}></Icon>
