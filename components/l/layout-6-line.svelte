<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6om7i3xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6om7i3xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-6-line" {...props}></Icon>
