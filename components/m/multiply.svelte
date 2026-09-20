<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfo0vldli.css';
import '../../css/o/o6jd39oeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hfo0vldli"/><path class="o6jd39oeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:multiply" {...props}></Icon>
