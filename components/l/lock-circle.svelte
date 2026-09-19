<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swz4mknri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="swz4mknri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-circle" {...props}></Icon>
