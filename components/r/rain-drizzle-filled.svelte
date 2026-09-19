<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-i9tb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si-i9tb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rain-drizzle-filled" {...props}></Icon>
