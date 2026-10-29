<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/c4zha4pqg.css';
import '../../css/z/zm4a7nbhr.css';
import '../../css/y/ysb5mhoxk.css';
import '../../css/i/inyg7ob9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="c4zha4pqg wm-deco"/><path class="wm-deco zm4a7nbhr"/><path class="ysb5mhoxk"/><path class="inyg7ob9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bold-blueprint" {...props}></Icon>
