<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njq90-bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njq90-bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-on-30" {...props}></Icon>
