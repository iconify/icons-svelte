<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n8ju1ahng.css';
import '../../css/g/gr8rvhted.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n8ju1ahng"/><path class="gr8rvhted"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:log-in" {...props}></Icon>
