<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qs96w4bbe.css';
import '../../css/e/eh36yibok.css';
import '../../css/o/ohgkzfgww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qs96w4bbe"/><path class="eh36yibok"/><path class="ohgkzfgww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:burger-solid" {...props}></Icon>
