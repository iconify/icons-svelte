<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj_f8me5y.css';
import '../../css/l/ljxqdzyof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jj_f8me5y"/><path class="ljxqdzyof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image-medical" {...props}></Icon>
