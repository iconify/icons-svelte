<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkll9tb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkll9tb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-duocolor-round" {...props}></Icon>
