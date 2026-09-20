<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f9f712xji.css';
import '../../css/g/gc65e_bcj.css';
import '../../css/o/o3umnd9gz.css';
import '../../css/f/f-ijmyb5m.css';
import '../../css/j/j11jiotsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f9f712xji"/><path class="gc65e_bcj"/><path class="o3umnd9gz"/><path class="f-ijmyb5m"/><path class="j11jiotsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-old-bold-duotone" {...props}></Icon>
