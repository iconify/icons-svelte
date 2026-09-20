<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anv572byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anv572byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-bar-increasing" {...props}></Icon>
