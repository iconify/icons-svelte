<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et29cpbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="et29cpbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reactive-resume" {...props}></Icon>
