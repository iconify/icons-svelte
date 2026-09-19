<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa5486b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa5486b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-start-vertical" {...props}></Icon>
