<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsf8c2b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsf8c2b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:fullscreen-exit" {...props}></Icon>
