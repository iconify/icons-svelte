<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8j6vh2mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8j6vh2mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baseball-2-fill" {...props}></Icon>
