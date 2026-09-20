<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3vyvrbyw.css';
import '../../css/e/el2jujohs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3vyvrbyw"/><path class="el2jujohs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:look-right-line" {...props}></Icon>
