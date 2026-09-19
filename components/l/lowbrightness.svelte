<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uddk3r85r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uddk3r85r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lowbrightness" {...props}></Icon>
