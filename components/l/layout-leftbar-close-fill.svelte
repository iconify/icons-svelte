<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myx2facns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myx2facns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-leftbar-close-fill" {...props}></Icon>
