<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymj-b0-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iymj-b0-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:codex" {...props}></Icon>
