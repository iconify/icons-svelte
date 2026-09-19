<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax753pv4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ax753pv4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:magic-wand" {...props}></Icon>
