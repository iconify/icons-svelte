<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opaq2dbry.css';
import '../../css/r/rqqek-bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="opaq2dbry"/><path class="rqqek-bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-alerting" {...props}></Icon>
