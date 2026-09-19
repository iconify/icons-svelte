<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj-xp5bcy.css';
import '../../css/y/ym37o3bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mj-xp5bcy"/><path class="ym37o3bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:agi" {...props}></Icon>
