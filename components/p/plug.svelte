<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpwcj4boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpwcj4boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:plug" {...props}></Icon>
