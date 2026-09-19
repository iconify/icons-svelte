<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkhncqomu.css';
import '../../css/i/ictwwwp8x.css';
import '../../css/t/tkitebcnv.css';
import '../../css/f/f4o7dgpcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="pkhncqomu"/><path class="ictwwwp8x"/><path class="tkitebcnv"/><path class="f4o7dgpcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ps-4x3" {...props}></Icon>
