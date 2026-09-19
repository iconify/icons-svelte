<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/e/e4x6eqq0d.css';
import '../../css/n/nix0j7bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="e4x6eqq0d"/><path class="nix0j7bwb"/><line x1="11" x2="11" y1="14" y2="22"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:boxing" {...props}></Icon>
