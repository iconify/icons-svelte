<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjh9_9bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjh9_9bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reload-round" {...props}></Icon>
