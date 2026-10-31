<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqu48-7cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqu48-7cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-treemap-fill-round" {...props}></Icon>
