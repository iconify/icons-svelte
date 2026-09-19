<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvn3mq7pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvn3mq7pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:laboratory" {...props}></Icon>
