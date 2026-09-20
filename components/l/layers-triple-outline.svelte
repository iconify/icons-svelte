<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai7gqpb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai7gqpb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers-triple-outline" {...props}></Icon>
