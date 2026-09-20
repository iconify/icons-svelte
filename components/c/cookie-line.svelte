<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/burq9xbdf.css';
import '../../css/v/vjz9f7byi.css';
import '../../css/z/zt0bu9e2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="burq9xbdf"/><path class="vjz9f7byi"/><path class="zt0bu9e2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cookie-line" {...props}></Icon>
