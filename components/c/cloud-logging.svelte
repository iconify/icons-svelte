<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbfqc9ipi.css';
import '../../css/o/oi7_5_auk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cbfqc9ipi"/><path class="oi7_5_auk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-logging" {...props}></Icon>
