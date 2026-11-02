<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxk8ojvuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxk8ojvuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:firecracker-fill" {...props}></Icon>
