<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dds184q7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dds184q7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-shield" {...props}></Icon>
