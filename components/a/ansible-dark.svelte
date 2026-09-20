<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjbp16bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjbp16bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ansible-dark" {...props}></Icon>
