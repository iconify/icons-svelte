<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzndz51eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzndz51eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pencil-ai-24" {...props}></Icon>
