<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__ieh4fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="b__ieh4fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:forward-30" {...props}></Icon>
