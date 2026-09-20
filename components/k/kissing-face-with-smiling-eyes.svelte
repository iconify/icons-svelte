<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7hstbmu.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/o/o3rhviknj.css';
import '../../css/s/sgor8wbzm.css';
import '../../css/o/oteit1bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="dcqdxh5zc"><path class="o3rhviknj"/><circle class="sgor8wbzm"/><path class="oteit1bml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:kissing-face-with-smiling-eyes" {...props}></Icon>
