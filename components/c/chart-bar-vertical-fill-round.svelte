<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l54gbmbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l54gbmbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-vertical-fill-round" {...props}></Icon>
