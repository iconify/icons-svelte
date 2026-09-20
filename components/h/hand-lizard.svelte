<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjyr4sbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rjyr4sbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-lizard" {...props}></Icon>
