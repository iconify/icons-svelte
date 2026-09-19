<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os_e7fbgt.css';
import '../../css/b/b8g_udb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="os_e7fbgt"/><path class="b8g_udb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chip" {...props}></Icon>
