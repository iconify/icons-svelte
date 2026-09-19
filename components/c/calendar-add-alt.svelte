<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzxfrybrb.css';
import '../../css/g/gxe7jmbor.css';
import '../../css/t/tp9_xo__k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zzxfrybrb"/><path class="gxe7jmbor"/><path class="tp9_xo__k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:calendar-add-alt" {...props}></Icon>
