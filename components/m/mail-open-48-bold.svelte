<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2je0ebuv.css';
import '../../css/f/f0_0fq_hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t2je0ebuv"/><path class="f0_0fq_hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-open-48-bold" {...props}></Icon>
