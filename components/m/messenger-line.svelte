<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3qf76brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qf76brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:messenger-line" {...props}></Icon>
