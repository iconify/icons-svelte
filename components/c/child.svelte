<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdvsm5ash.css';
import '../../css/s/sm0fnnq5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdvsm5ash"/><path class="sm0fnnq5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:child" {...props}></Icon>
