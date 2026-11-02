<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox0swvb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox0swvb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lectern-fill" {...props}></Icon>
