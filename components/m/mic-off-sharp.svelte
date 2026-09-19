<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyk9gzbzx.css';
import '../../css/g/g1pzq4t8l.css';
import '../../css/j/jucagptoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tyk9gzbzx"/><path class="g1pzq4t8l"/><path class="jucagptoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:mic-off-sharp" {...props}></Icon>
