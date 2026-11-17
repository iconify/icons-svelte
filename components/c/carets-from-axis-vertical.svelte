<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-8o074js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-8o074js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:carets-from-axis-vertical" {...props}></Icon>
