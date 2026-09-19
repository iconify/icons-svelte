<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg-yxldyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg-yxldyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:reolink-820" {...props}></Icon>
