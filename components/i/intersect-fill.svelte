<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3qdevbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3qdevbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:intersect-fill" {...props}></Icon>
