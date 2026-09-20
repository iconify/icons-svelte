<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_oews0vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a_oews0vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:historic" {...props}></Icon>
