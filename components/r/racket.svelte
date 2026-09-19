<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grb34gbeb.css';
import '../../css/m/mlcrs6b_l.css';
import '../../css/n/ne1pfgevp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="grb34gbeb"/><path class="mlcrs6b_l"/><path class="ne1pfgevp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:racket" {...props}></Icon>
