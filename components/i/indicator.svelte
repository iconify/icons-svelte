<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhomer8zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yhomer8zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:indicator" {...props}></Icon>
