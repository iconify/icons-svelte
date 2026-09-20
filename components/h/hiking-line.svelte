<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh-z6dbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh-z6dbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hiking-line" {...props}></Icon>
