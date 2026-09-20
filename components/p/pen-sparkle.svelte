<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fsade8bxv.css';
import '../../css/f/f6rz0s9bl.css';
import '../../css/z/z571ntbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fsade8bxv"/><path class="f6rz0s9bl"/><circle class="z571ntbme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen-sparkle" {...props}></Icon>
