<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfj231j0y.css';
import '../../css/a/ayfs0cb5s.css';
import '../../css/w/wdxqc5bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="sfj231j0y"/><path class="ayfs0cb5s"/><path class="wdxqc5bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fullmoonwithface" {...props}></Icon>
