<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsku-rbch.css';
import '../../css/i/in_k0mbzy.css';
import '../../css/d/dc6crytza.css';
import '../../css/m/mndorw7al.css';
import '../../css/c/caf4nbbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vsku-rbch"/><path class="in_k0mbzy"/><path class="dc6crytza"/><path class="mndorw7al"/><path class="caf4nbbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floating-wind-20-bold" {...props}></Icon>
