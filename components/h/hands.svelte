<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlpmhkb0y.css';
import '../../css/a/arjp9mitp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mlpmhkb0y"/><path class="arjp9mitp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:hands" {...props}></Icon>
