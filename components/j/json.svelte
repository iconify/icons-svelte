<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkd76en_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lkd76en_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:json" {...props}></Icon>
