<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_mk7bzxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_mk7bzxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-check-fill-round" {...props}></Icon>
