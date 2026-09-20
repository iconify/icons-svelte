<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ish5habrg.css';
import '../../css/o/oo48_6r0q.css';
import '../../css/x/xkadkob3k.css';
import '../../css/y/y92gimbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ish5habrg"/><circle class="oo48_6r0q"/><circle class="xkadkob3k"/><circle class="y92gimbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:jupyter" {...props}></Icon>
