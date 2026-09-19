<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkcrs2b2j.css';
import '../../css/h/hrklssb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkcrs2b2j"/><path class="hrklssb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:asset-confirm" {...props}></Icon>
