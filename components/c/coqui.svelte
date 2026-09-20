<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_dnl3bgj.css';
import '../../css/o/ote0d1bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_dnl3bgj"/><path class="ote0d1bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coqui" {...props}></Icon>
