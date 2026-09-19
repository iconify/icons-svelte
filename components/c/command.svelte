<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gre2h1byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gre2h1byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:command" {...props}></Icon>
