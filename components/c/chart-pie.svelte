<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsnlamvum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lsnlamvum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-pie" {...props}></Icon>
