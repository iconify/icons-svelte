<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scg-lw7vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scg-lw7vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-outline" {...props}></Icon>
