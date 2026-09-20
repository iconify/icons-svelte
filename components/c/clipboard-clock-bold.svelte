<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s0-mqwb2a.css';
import '../../css/d/dih0g1b-s.css';
import '../../css/c/c3lyyzb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s0-mqwb2a"/><path clip-rule="evenodd" class="dih0g1b-s"/><path class="c3lyyzb8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-clock-bold" {...props}></Icon>
