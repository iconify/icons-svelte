<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk4a13bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4a13bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notification-line" {...props}></Icon>
