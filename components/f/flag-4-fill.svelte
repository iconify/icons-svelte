<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q16-r7rou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q16-r7rou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-4-fill" {...props}></Icon>
