<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqcy64bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqcy64bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plug-off" {...props}></Icon>
