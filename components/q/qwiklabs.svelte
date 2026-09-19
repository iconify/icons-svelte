<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzwavbc0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzwavbc0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:qwiklabs" {...props}></Icon>
