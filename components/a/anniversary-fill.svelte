<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orce8znyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orce8znyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anniversary-fill" {...props}></Icon>
