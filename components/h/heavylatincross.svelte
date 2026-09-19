<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggdspccqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggdspccqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heavylatincross" {...props}></Icon>
