<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu0lojbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0lojbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-minus-2-line" {...props}></Icon>
