<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rap11obza.css';
import '../../css/a/ax3lz4b9z.css';
import '../../css/g/ga7t0girt.css';
import '../../css/e/ef0vyen_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rap11obza"/><circle class="ax3lz4b9z"/><path class="ga7t0girt"/><path class="ef0vyen_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:passport-line-duotone" {...props}></Icon>
