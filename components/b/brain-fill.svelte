<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg3lhxc0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg3lhxc0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brain-fill" {...props}></Icon>
