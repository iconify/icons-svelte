<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/laf_138jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="laf_138jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-justify-solid" {...props}></Icon>
