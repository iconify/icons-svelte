<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9q7kbbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9q7kbbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-left-down-solid" {...props}></Icon>
