<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb8ysxktc.css';
import '../../css/r/r6esm02yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lb8ysxktc"/><path class="r6esm02yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-open" {...props}></Icon>
