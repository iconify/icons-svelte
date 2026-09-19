<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu5k5fb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu5k5fb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:github-copilot" {...props}></Icon>
