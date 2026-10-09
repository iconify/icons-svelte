<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubfb-9idi.css';
import '../../css/o/o0mm69boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubfb-9idi"/><path class="o0mm69boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noise-reduction-20-bold" {...props}></Icon>
