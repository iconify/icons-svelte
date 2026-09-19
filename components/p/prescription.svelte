<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjzu1bbsy.css';
import '../../css/h/hhnaxiuju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="pjzu1bbsy"/><path class="hhnaxiuju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:prescription" {...props}></Icon>
