<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3jglccvf.css';
import '../../css/c/cuikm_bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="r3jglccvf"/><path class="cuikm_bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:arrow-turn-right" {...props}></Icon>
