<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7a4tsbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q7a4tsbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dot-dashed-duotone" {...props}></Icon>
