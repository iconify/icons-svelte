<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqle92b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqle92b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:indent-decrease-line" {...props}></Icon>
