<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py_7xmyxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py_7xmyxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-right-down-sharp-two-tone" {...props}></Icon>
