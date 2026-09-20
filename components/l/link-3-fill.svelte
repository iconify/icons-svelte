<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbj4o1-vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbj4o1-vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-3-fill" {...props}></Icon>
