<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwtxp2blp.css';
import '../../css/k/kkn84ffqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pwtxp2blp"/><path class="kkn84ffqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:right-arrow-curving-up" {...props}></Icon>
