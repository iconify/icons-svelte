<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4iehlbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i4iehlbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:drone" {...props}></Icon>
