<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2woclr0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p2woclr0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:electron" {...props}></Icon>
