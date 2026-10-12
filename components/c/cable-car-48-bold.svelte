<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwvj6mb8y.css';
import '../../css/m/mz-9qgswv.css';
import '../../css/v/vao3mhbsj.css';
import '../../css/g/g87xp5bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gwvj6mb8y"/><path class="mz-9qgswv"/><path class="vao3mhbsj"/><path class="g87xp5bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-car-48-bold" {...props}></Icon>
