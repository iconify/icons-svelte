<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4-z3mbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4-z3mbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bulwark-dark" {...props}></Icon>
