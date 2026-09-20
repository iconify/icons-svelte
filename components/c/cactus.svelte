<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/denthcbya.css';
import '../../css/r/roadlpwdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="denthcbya"/><path class="roadlpwdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cactus" {...props}></Icon>
