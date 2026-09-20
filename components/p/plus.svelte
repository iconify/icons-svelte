<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6hb5h4da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="i6hb5h4da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:plus" {...props}></Icon>
