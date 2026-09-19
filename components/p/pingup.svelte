<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mquy8vb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mquy8vb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:pingup" {...props}></Icon>
