<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oay8kys0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oay8kys0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-large-fill-round" {...props}></Icon>
