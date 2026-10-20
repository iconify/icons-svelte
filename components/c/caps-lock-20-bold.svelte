<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9h1pi52i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r9h1pi52i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caps-lock-20-bold" {...props}></Icon>
