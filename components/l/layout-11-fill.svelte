<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8tagfb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8tagfb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-11-fill" {...props}></Icon>
