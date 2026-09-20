<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iabj60bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iabj60bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:escalator-descend-bold" {...props}></Icon>
