<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnd39cc7h.css';
import '../../css/j/j7hpihb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mnd39cc7h"/><path class="j7hpihb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:drone-front" {...props}></Icon>
