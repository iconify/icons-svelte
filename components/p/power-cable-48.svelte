<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0_z3bkf.css';
import '../../css/f/fg9x0cckk.css';
import '../../css/z/z8mmwq-ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ln0_z3bkf"/><path class="fg9x0cckk"/><path class="z8mmwq-ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-cable-48" {...props}></Icon>
