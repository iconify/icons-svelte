<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5xztqbch.css';
import '../../css/o/orxho49no.css';
import '../../css/k/kfbs23bbk.css';
import '../../css/r/rdzvzrz1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w5xztqbch"/><path class="orxho49no"/><path class="kfbs23bbk"/><path class="rdzvzrz1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-well-20-bold" {...props}></Icon>
