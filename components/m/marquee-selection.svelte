<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qay0ro2fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qay0ro2fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:marquee-selection" {...props}></Icon>
